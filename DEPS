# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b6685947cd6f5dbc7dd80a1c73e0171c9b7505f9',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7df1088fce85996c35452ddc92df24eb4384363f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1f2dd1627ae782fa999b6ed86514c6a905438e3c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c98fc83591a0b01d68f929478b59d3bdd7f00fc6',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8864cdc896bbc2a9b6eb36b3218fc9ef57908d77',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '073ca9f6f2073e18c1294b519710f68b21370db5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5d40749670ccde08fd91412d3daa074615940d6a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a96bd4933c6adfc21329d15e9999791a0153bbf3',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f8c80e1c0bbbd708ca9dcce9054364514825e5b7',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
