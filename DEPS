# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e4c40890710586ea02a2d457a123b7c339d526f7',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '02acf732d259379c4e4f296e4a6a6b6c8173c878',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '465055f6c9128772e20082e893d974146acf7a02',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8a13595dd4ae5049ef42d0f30297d0c427db54b5',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f07ffc2cf2cd356927dee964fc0a35b5cfaeb789',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1a588f1982c14309873f2a86a60cfbfe5fb249f8',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '90bf5bc4fd8bea0d300f6564af256a51a34124b8',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5cbca997c1f916026670ffc8d6890ef9f1cd788d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '02eeaa5bee98fd67e719bb7f8101a49420bd878a',
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
