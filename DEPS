# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b11e161935ddd143df9e070834e62d94377043b8',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e3782cba07b8b479bf194ac9d811bd3a09261aba',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f1fa5178eced755a189619b8e4546bcc2ce69fdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1d0401cd2b68ae34cda9ff625bedd1be4ed6214a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6802bb4733b63ed5efd3adb308a6c885ef180ea1',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd2ef0c162c4ed997cff870f2f0914f52b23f2401',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6fe2055cf2fa921d52a4c6a31528cfc279a6977f',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '89042504f261a90d835bac9de636820a0fe7a4cf',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9468778ec1b322d160374be8ff7a831351a9edb6',
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
