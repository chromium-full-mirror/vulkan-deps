# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '716f9503264d539cc05503cae562e6949eada8f5',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7df1088fce85996c35452ddc92df24eb4384363f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '126038020c2bd47efaa942ccc364ca5353ffccde',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c98fc83591a0b01d68f929478b59d3bdd7f00fc6',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8864cdc896bbc2a9b6eb36b3218fc9ef57908d77',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a9e72c66d5cb79911eb9a9063bf4016dd0a3a123',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1cb3a319969cf0d3e2315b0a87a27447f55b4167',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a96bd4933c6adfc21329d15e9999791a0153bbf3',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7b18aa921180e7391298fd2cfaa37152f9e427d4',
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
