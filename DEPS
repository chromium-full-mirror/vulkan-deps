# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5ccb61590f533d4c8b12921ead86bf1e2d35e0e9',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e1013f570e4fab64a29328dd75c925ce8888e181',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '1f2dd1627ae782fa999b6ed86514c6a905438e3c',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6337eb62cadd7d124ac6789bf39c0f71148f0a73',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '7f233bc128bebd91c914ddc3678aa970828031d6',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fc1daa956375aacd8c7fbdbaa0579f061c932416',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd2994039d549970c5d8f60603209a947c5241cb2',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'd88097b51e70f357a96237c4571ded3433ccde99',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3df3a20c5b9494a54b0c59658bdc9f311a4f9e81',
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
